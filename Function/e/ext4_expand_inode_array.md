# Function: <code>ext4_expand_inode_array</code>

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
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582230250,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2750",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582378688,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2786",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582569523,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2803",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582670915,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2808",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582843759,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582947903,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260016,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2796",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260016,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583360944,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2803",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360944,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583384256,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2803",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384256,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583728512,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2786",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728512,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584284288,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2801",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284288,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584932256,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2827",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584932256,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159760,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2874",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159760,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585392432,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2874",
      "file": "fs/ext4/xattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585392432,
      "name": "ext4_expand_inode_array",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494628312,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228068424,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288429532,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273996556,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582916639,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582853791,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582905247,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_expand_inode_array",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582992319,
      "name": "ext4_expand_inode_array",
      "external": false,
      "loc": "fs/ext4/xattr.c:2809",
      "file": "fs/ext4/xattr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array * * ea_inode_array, struct inode * inode)
```
</details>
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
