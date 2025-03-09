# Function: <code>__ext4_block_zero_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581569442,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3404",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
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
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581754258,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3678",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
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
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581842418,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3797",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
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
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581992065,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3917",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
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
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582141601,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3966",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
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
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582330625,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3978",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
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
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582429230,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4011",
      "file": "fs/ext4/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582598384,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4024",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582598384,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582699120,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582699120,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583011040,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3693",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583011040,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 942
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086512,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3731",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086512,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583111520,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3730",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583111520,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3653",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451152,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 757
    },
    {
      "addr": 18446744071592258523,
      "name": "__ext4_block_zero_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3718",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972896,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
    },
    {
      "addr": 18446744071594039763,
      "name": "__ext4_block_zero_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3804",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584600912,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 879
    },
    {
      "addr": 18446744071596072765,
      "name": "__ext4_block_zero_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3589",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827136,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
    },
    {
      "addr": 18446744071596596267,
      "name": "__ext4_block_zero_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:3608",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585060112,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 730
    },
    {
      "addr": 18446744071597501786,
      "name": "__ext4_block_zero_page_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494355960,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494355960,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227789208,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227789208,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1340
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288085696,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288085696,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1632
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273785494,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273785494,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667856,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667856,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605024,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605024,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582657712,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582657712,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1331
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
```

```json
{
  "name": "__ext4_block_zero_page_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741392,
      "name": "__ext4_block_zero_page_range",
      "external": false,
      "loc": "fs/ext4/inode.c:4001",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_block_zero_page_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741392,
      "name": "__ext4_block_zero_page_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1348
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
int __ext4_block_zero_page_range(handle_t * handle, struct address_space * mapping, loff_t from, loff_t length)
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
