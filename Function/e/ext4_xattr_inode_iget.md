# Function: <code>ext4_xattr_inode_iget</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582228560,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:357",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228560,
      "name": "ext4_xattr_inode_iget.isra.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582375664,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:360",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582375664,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582566464,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582566464,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667888,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667888,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582841648,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582841648,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582945792,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582945792,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262912,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:383",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262912,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363808,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:383",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363808,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386528,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:383",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583386528,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730880,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:383",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730880,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584283440,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:383",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283440,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931376,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:385",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931376,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585158960,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:423",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158960,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585391600,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:423",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_inc_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585391600,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494624808,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494624808,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228063800,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228063800,
      "name": "ext4_xattr_inode_iget",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288424800,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288424800,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273993986,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273993986,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582914528,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914528,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582851680,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851680,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903136,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903136,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```

```json
{
  "name": "ext4_xattr_inode_iget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582990208,
      "name": "ext4_xattr_inode_iget",
      "external": false,
      "loc": "fs/ext4/xattr.c:381",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_set_entry",
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all",
        "fs/ext4/xattr.c:ext4_xattr_inode_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582990208,
      "name": "ext4_xattr_inode_iget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int ext4_xattr_inode_iget(struct inode * parent, long unsigned int ea_ino, u32 ea_inode_hash, struct inode * * ea_inode)
```
</details>
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
