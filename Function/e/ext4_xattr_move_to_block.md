# Function: <code>ext4_xattr_move_to_block</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582139810,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:1345",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582245520,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2494",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582394480,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2530",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582585286,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582686659,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2545",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582856816,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582856816,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582960976,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582960976,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275936,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2533",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_make_inode_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275936,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583377072,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2540",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_make_inode_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377072,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400000,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2540",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400000,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583744464,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2523",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583744464,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584301392,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2538",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301392,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 827
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949824,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2558",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949824,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 851
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585177888,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2601",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585177888,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585410672,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2601",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410672,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 995
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494638848,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228083908,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288446192,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288446192,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274008888,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582929712,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929712,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582866864,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866864,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582918320,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582918320,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```

```json
{
  "name": "ext4_xattr_move_to_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005376,
      "name": "ext4_xattr_move_to_block",
      "external": false,
      "loc": "fs/ext4/xattr.c:2546",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005376,
      "name": "ext4_xattr_move_to_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
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
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ext4_xattr_move_to_block(handle_t * handle, struct inode * inode, struct ext4_inode * raw_inode, struct ext4_xattr_entry * entry)
```
</details>
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
