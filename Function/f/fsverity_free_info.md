# Function: <code>fsverity_free_info</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582320980,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320912,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582322352,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582610227,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:231",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611712,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582682531,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:240",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684016,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582711315,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:213",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712400,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037955,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:213",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039040,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583512515,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:212",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583513648,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584110323,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:212",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111856,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584336099,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:271",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:__fsverity_cleanup_inode",
        "fs/verity/open.c:__fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584337936,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584554307,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:271",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:__fsverity_cleanup_inode",
        "fs/verity/open.c:__fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556144,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493902068,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493901976,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446603336493904016,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227380844,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227380760,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3227382784,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287538784,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287538656,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055287541328,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273458542,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273458456,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936273460276,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582289716,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582289648,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582291088,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582227476,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227408,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582228848,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582280196,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280128,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582281568,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```

```json
{
  "name": "fsverity_free_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582358756,
      "name": "fsverity_free_info",
      "external": true,
      "loc": "fs/verity/open.c:230",
      "file": "fs/verity/open.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ],
      "caller_func": [
        "fs/verity/enable.c:enable_verity",
        "fs/verity/enable.c:enable_verity",
        "fs/verity/open.c:fsverity_cleanup_inode",
        "fs/verity/open.c:fsverity_set_info",
        "fs/verity/open.c:fsverity_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358688,
      "name": "fsverity_free_info.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582360128,
      "name": "fsverity_free_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void fsverity_free_info(struct fsverity_info * vi)
```
</details>
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
