# Function: <code>ext4_ext_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738768,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3118",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738768,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933696,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3140",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933696,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023760,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3140",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023760,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886480,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3141",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886480,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582036512,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3141",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036512,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224848,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3135",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224848,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319760,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3197",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_ext_handle_unwritten_extents",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319760,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486864,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3217",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486864,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586112,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586112,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582919970,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3100",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582991755,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3099",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583016906,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3102",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583354384,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3140",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583864472,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3139",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584488712,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3144",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584717430,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3144",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584950518,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3120",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494235968,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494235968,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227668740,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227668740,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287939472,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287939472,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273690524,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273690524,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582554848,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554848,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492016,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492016,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582544960,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544960,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
```

```json
{
  "name": "ext4_ext_zeroout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626080,
      "name": "ext4_ext_zeroout",
      "external": false,
      "loc": "fs/ext4/extents.c:3263",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_ext_convert_to_initialized",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at",
        "fs/ext4/extents.c:ext4_split_extent_at"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626080,
      "name": "ext4_ext_zeroout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int ext4_ext_zeroout(struct inode * inode, struct ext4_extent * ex)
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
