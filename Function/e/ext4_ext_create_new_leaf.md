# Function: <code>ext4_ext_create_new_leaf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749006,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1347",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581943656,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1353",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582033688,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1353",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581895934,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1353",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582046110,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1353",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582239337,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1347",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582335257,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1347",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582501008,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582501008,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582601104,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582601104,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912512,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1345",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912512,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984336,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1343",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984336,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583011893,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1346",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583349000,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1388",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583859102,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1390",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584483278,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1398",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584712073,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1398",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584945097,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1398",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494251192,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494251192,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227683232,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227683232,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287961984,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273701502,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273701502,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 702
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582569840,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569840,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582507008,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582507008,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559952,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559952,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 850
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```

```json
{
  "name": "ext4_ext_create_new_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582641168,
      "name": "ext4_ext_create_new_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:1364",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_insert_extent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641168,
      "name": "ext4_ext_create_new_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
```
</details>
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
int ext4_ext_create_new_leaf(handle_t * handle, struct inode * inode, unsigned int mb_flags, unsigned int gb_flags, struct ext4_ext_path * * ppath, struct ext4_extent * newext)
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
