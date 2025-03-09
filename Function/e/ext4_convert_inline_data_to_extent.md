# Function: <code>ext4_convert_inline_data_to_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581862518,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:520",
      "file": "fs/ext4/inline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
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
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582058396,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:520",
      "file": "fs/ext4/inline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
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
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582148044,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:531",
      "file": "fs/ext4/inline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
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
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581967701,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:534",
      "file": "fs/ext4/inline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
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
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582116741,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
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
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582305137,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
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
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582403761,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582569840,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582569840,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582670800,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582670800,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582984432,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984432,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1134
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583060032,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583060032,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1128
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583085440,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583085440,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1126
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424512,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:529",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424512,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583941792,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:533",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583941792,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1385
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584568416,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:532",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584568416,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1398
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584796640,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:542",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584796640,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585029520,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:541",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029520,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1014
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494323336,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494323336,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227758892,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227758892,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288047344,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288047344,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1768
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273762350,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273762350,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1036
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582639536,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582639536,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582576704,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582576704,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582629392,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582629392,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "ext4_convert_inline_data_to_extent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582712624,
      "name": "ext4_convert_inline_data_to_extent",
      "external": false,
      "loc": "fs/ext4/inline.c:525",
      "file": "fs/ext4/inline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712624,
      "name": "ext4_convert_inline_data_to_extent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1256
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
int ext4_convert_inline_data_to_extent(struct address_space * mapping, struct inode * inode, unsigned int flags)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
