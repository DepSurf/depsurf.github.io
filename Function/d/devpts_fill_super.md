# Function: <code>devpts_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581523852,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:377",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_mount"
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
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581709654,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:395",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_mount"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581797168,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:389",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581797168,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581868288,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:422",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581868288,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582018272,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:450",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018272,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:450",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206688,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
    },
    {
      "addr": 18446744071582208628,
      "name": "devpts_fill_super.cold.9",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582301917,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:448",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301728,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
    },
    {
      "addr": 18446744071582303475,
      "name": "devpts_fill_super.cold.7",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582468271,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468080,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071582469899,
      "name": "devpts_fill_super.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582567215,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582567024,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071582568843,
      "name": "devpts_fill_super.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875488,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071582877272,
      "name": "devpts_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582948352,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
    },
    {
      "addr": 18446744071591346684,
      "name": "devpts_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582975568,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071591289380,
      "name": "devpts_fill_super.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583311168,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071592249339,
      "name": "devpts_fill_super.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583818432,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 598
    },
    {
      "addr": 18446744071594030406,
      "name": "devpts_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584440480,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440480,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669264,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:427",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669264,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584902032,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:426",
      "file": "fs/devpts/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902032,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494212656,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494212656,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227644024,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227644024,
      "name": "devpts_fill_super",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287907856,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287907856,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273670902,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273670902,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582535951,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535760,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071582537579,
      "name": "devpts_fill_super.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582473119,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472928,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071582474747,
      "name": "devpts_fill_super.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582526431,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582526240,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071582528059,
      "name": "devpts_fill_super.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```

```json
{
  "name": "devpts_fill_super",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582607103,
      "name": "devpts_fill_super",
      "external": false,
      "loc": "fs/devpts/inode.c:445",
      "file": "fs/devpts/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606912,
      "name": "devpts_fill_super",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 610
    },
    {
      "addr": 18446744071582608731,
      "name": "devpts_fill_super.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int devpts_fill_super(struct super_block * s, void * data, int silent)
```
</details>
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
